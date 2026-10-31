<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/arptzobve.css';
import '../../css/a/aey1x7bcf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="arptzobve"/><path class="aey1x7bcf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:monaco" {...props}></Icon>
