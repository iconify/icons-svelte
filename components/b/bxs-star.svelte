<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f_56uhald.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f_56uhald"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-star" {...props}></Icon>
