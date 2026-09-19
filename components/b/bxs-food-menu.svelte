<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c210-8tfy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c210-8tfy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-food-menu" {...props}></Icon>
