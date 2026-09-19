<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cpi0e_ttd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="cpi0e_ttd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:geo-alt-fill" {...props}></Icon>
