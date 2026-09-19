<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vw3w1xvfl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vw3w1xvfl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-tag-x" {...props}></Icon>
