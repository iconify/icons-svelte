<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qr6ni573u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qr6ni573u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:folder-up" {...props}></Icon>
