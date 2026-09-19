<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aech68a0h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="aech68a0h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:check-lg-fill-16" {...props}></Icon>
