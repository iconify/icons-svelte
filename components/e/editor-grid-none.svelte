<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-f5jnbcl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="m-f5jnbcl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:editor-grid-none" {...props}></Icon>
