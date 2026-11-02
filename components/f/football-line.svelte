<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w9s6pabbs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w9s6pabbs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:football-line" {...props}></Icon>
