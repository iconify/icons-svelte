<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t-8dx3e7s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t-8dx3e7s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:blender" {...props}></Icon>
