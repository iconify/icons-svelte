<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hdn_9obuu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hdn_9obuu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:arrow-top-left-1-bold" {...props}></Icon>
