<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z3ib1ob1k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z3ib1ob1k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:eraser" {...props}></Icon>
