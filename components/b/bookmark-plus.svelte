<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y_l8fib7s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-5,"top":-2};
const content = `<path class="y_l8fib7s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:bookmark-plus" {...props}></Icon>
