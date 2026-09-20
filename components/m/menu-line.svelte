<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hzku5q1zv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hzku5q1zv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:menu-line" {...props}></Icon>
