<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ki54017ia.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ki54017ia"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:check-check-20-bold" {...props}></Icon>
