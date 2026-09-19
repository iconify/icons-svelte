<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rz2-bqx6h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rz2-bqx6h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:android-menu" {...props}></Icon>
