<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ydjm23-rr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="ydjm23-rr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:chess-bishop" {...props}></Icon>
