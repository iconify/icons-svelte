<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cug31wb8h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="cug31wb8h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:heptagon" {...props}></Icon>
