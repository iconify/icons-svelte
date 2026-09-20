<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e25_79bky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e25_79bky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:minus-square-line" {...props}></Icon>
