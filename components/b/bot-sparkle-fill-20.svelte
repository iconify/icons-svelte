<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wdcxh6dac.css';
import '../../css/r/rsf6pbc-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="wdcxh6dac"/><path class="rsf6pbc-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:bot-sparkle-fill-20" {...props}></Icon>
