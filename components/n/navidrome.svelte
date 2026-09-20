<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yvspe7bge.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yvspe7bge"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:navidrome" {...props}></Icon>
