<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/odgb6sblx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="odgb6sblx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:eye-cancelled-filled" {...props}></Icon>
