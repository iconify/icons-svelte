<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xp0lh4b9h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xp0lh4b9h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:certificate-success-filled" {...props}></Icon>
