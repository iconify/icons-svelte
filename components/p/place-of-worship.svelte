<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qxc3k3jzd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="qxc3k3jzd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:place-of-worship" {...props}></Icon>
