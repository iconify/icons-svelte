<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j8x5w1b7i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j8x5w1b7i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:list-filter" {...props}></Icon>
