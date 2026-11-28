<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ki8kgzomh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ki8kgzomh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:pin-drop-check" {...props}></Icon>
