<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bxzhhfb8u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="bxzhhfb8u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:interpreter-filled" {...props}></Icon>
