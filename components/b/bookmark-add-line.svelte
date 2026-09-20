<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jjhhhdbtb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jjhhhdbtb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:bookmark-add-line" {...props}></Icon>
