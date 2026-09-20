<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i4jwp3d8w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="i4jwp3d8w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:check-out" {...props}></Icon>
