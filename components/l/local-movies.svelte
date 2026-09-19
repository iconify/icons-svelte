<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kdd-yccal.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":344,"height":384};
const content = `<path class="kdd-yccal"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:local-movies" {...props}></Icon>
