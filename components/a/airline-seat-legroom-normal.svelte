<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pzo1he64y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":408,"height":384};
const content = `<path class="pzo1he64y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:airline-seat-legroom-normal" {...props}></Icon>
