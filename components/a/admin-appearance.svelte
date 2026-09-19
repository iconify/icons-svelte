<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qre1wn1gl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="qre1wn1gl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:admin-appearance" {...props}></Icon>
