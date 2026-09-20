<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lbo3mlqmu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="lbo3mlqmu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:phoenix-squadron" {...props}></Icon>
