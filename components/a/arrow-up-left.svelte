<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ms-oo7b_h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ms-oo7b_h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:arrow-up-left" {...props}></Icon>
