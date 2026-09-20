<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ceeknj_js.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="ceeknj_js"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:owm-night-211" {...props}></Icon>
