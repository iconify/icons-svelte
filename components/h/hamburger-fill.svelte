<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ry1fr0bqy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ry1fr0bqy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:hamburger-fill" {...props}></Icon>
