<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fib0t9bty.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fib0t9bty"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:hard-hat-check" {...props}></Icon>
