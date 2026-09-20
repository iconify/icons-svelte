<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zgumdy88r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zgumdy88r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:htc" {...props}></Icon>
