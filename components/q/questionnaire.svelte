<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uj7jp6vjo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="uj7jp6vjo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:questionnaire" {...props}></Icon>
