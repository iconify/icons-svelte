<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d6o0vlrtm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="d6o0vlrtm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:cash-register" {...props}></Icon>
