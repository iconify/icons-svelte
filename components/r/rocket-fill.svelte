<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ilgc15b5q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ilgc15b5q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:rocket-fill" {...props}></Icon>
