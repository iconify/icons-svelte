<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/phx7tstox.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="phx7tstox"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:filter" {...props}></Icon>
