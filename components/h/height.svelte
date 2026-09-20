<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e1j0nabvc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="e1j0nabvc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:height" {...props}></Icon>
