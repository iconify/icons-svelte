<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gxxtszp8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gxxtszp8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-cyber:cursor-arrow-1" {...props}></Icon>
