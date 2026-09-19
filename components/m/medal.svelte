<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mw03xnjge.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mw03xnjge"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:medal" {...props}></Icon>
