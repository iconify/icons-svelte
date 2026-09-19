<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f_b2_4b1k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f_b2_4b1k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-cabinet" {...props}></Icon>
