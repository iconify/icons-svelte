<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qh57bvagt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="qh57bvagt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:chevron-right-bar-small" {...props}></Icon>
