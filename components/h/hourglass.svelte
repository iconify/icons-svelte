<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bf4n8dbvk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="bf4n8dbvk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:hourglass" {...props}></Icon>
