<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i8lv4dbma.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i8lv4dbma"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:microscope" {...props}></Icon>
