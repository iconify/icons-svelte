<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fffub0b_c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="fffub0b_c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:amilia" {...props}></Icon>
