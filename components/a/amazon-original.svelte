<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vlxyymbyb.css';
import '../../css/w/wgvkkuyqy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vlxyymbyb"/><path class="wgvkkuyqy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:amazon-original" {...props}></Icon>
