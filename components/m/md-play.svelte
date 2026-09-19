<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/exwu-touj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="exwu-touj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-play" {...props}></Icon>
