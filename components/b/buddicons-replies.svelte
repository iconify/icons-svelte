<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fd4_62byz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="fd4_62byz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:buddicons-replies" {...props}></Icon>
