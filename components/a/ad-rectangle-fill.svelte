<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jkbuy5vok.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jkbuy5vok"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:ad-rectangle-fill" {...props}></Icon>
