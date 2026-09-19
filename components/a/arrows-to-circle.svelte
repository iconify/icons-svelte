<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qmto9yz5j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="qmto9yz5j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:arrows-to-circle" {...props}></Icon>
