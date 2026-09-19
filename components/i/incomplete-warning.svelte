<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mhouzo_0g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="mhouzo_0g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:incomplete-warning" {...props}></Icon>
