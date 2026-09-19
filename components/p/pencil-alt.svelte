<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ylte6_80y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ylte6_80y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:pencil-alt" {...props}></Icon>
