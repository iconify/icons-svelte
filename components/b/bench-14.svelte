<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ayk2_7bcq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="ayk2_7bcq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="osmic:bench-14" {...props}></Icon>
