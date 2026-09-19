<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n_cr8_bgb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="n_cr8_bgb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:diamond-fill" {...props}></Icon>
