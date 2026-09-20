<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c5al98e6o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c5al98e6o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:card-text" {...props}></Icon>
