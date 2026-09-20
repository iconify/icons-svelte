<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wjyda_60k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wjyda_60k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:reload" {...props}></Icon>
