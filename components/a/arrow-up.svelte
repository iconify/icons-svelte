<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r12wm_i0o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="r12wm_i0o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:arrow-up" {...props}></Icon>
