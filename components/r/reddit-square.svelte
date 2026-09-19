<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ppamt2b3k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1536};
const content = `<path class="ppamt2b3k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:reddit-square" {...props}></Icon>
