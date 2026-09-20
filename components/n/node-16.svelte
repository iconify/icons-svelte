<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/prz566bot.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="prz566bot"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:node-16" {...props}></Icon>
