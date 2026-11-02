<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cr36wacon.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cr36wacon"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:cloud-moon-rain-fill" {...props}></Icon>
