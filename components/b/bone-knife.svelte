<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/syige5y7k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="syige5y7k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:bone-knife" {...props}></Icon>
