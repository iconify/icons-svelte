<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o3p7h4o0c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="o3p7h4o0c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:pc-display" {...props}></Icon>
