<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vfkzubcqb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vfkzubcqb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:disc-fill" {...props}></Icon>
