<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ttu2v-2ik.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ttu2v-2ik"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:buddicons-pm" {...props}></Icon>
