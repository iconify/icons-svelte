<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f1u2uwnio.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":512};
const content = `<path class="f1u2uwnio"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:puzzle" {...props}></Icon>
