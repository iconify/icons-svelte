<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ej0p2x0ci.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ej0p2x0ci"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:piapro" {...props}></Icon>
