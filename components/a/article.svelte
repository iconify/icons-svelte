<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s2ol43b7k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s2ol43b7k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:article" {...props}></Icon>
