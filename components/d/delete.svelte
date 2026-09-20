<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d0yupbc9p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d0yupbc9p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:delete" {...props}></Icon>
