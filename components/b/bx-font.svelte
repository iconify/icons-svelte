<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d_q2xctkr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d_q2xctkr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-font" {...props}></Icon>
