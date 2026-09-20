<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vbq-w5j8i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="vbq-w5j8i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:media-step-forward" {...props}></Icon>
