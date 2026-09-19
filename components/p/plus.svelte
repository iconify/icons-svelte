<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/flyu6zhwi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":304,"height":384};
const content = `<path class="flyu6zhwi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:plus" {...props}></Icon>
