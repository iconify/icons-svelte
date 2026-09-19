<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b1ogv8bbs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b1ogv8bbs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-plus-square" {...props}></Icon>
