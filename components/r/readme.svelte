<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iovyd2lnb.css';
import '../../css/i/iio97lbyc.css';
import '../../css/e/e9vub8bzj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="iovyd2lnb"><path class="iio97lbyc"/><path class="e9vub8bzj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:readme" {...props}></Icon>
