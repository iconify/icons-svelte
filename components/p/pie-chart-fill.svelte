<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_bh4bwo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="nz_bh4bwo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:pie-chart-fill" {...props}></Icon>
