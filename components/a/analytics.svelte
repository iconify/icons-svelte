<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o0yrs3cgn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o0yrs3cgn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:analytics" {...props}></Icon>
