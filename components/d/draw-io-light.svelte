<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o9kcm970w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o9kcm970w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:draw-io-light" {...props}></Icon>
