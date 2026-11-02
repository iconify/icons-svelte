<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lcfquw3sp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lcfquw3sp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:reddit-line" {...props}></Icon>
