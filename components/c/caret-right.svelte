<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ykkm75j5q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ykkm75j5q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:caret-right" {...props}></Icon>
