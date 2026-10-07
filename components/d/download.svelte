<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cpe24tbjy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cpe24tbjy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:download" {...props}></Icon>
