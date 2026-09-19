<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f9j7slbwl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f9j7slbwl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:baseball-helmet" {...props}></Icon>
