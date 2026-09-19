<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gof7yqdxi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gof7yqdxi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:card-ace-diamonds" {...props}></Icon>
