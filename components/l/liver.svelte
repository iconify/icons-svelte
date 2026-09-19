<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yqdxep41r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yqdxep41r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:liver" {...props}></Icon>
