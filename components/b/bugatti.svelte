<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuosljb9z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cuosljb9z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:bugatti" {...props}></Icon>
