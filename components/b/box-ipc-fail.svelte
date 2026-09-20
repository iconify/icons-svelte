<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t4zn-mv5y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="t4zn-mv5y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:box-ipc-fail" {...props}></Icon>
