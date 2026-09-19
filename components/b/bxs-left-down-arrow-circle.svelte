<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f3ojxbk_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f3ojxbk_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-left-down-arrow-circle" {...props}></Icon>
