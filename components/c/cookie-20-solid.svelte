<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cz1unabkx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="cz1unabkx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:cookie-20-solid" {...props}></Icon>
