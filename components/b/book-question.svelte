<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cg8js6q3e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cg8js6q3e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:book-question" {...props}></Icon>
