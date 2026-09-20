<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/etcjt1s5b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="etcjt1s5b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:football-helmet" {...props}></Icon>
