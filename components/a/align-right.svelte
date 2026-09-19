<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ztbl4bbma.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ztbl4bbma"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:align-right" {...props}></Icon>
