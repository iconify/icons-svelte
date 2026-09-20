<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vu7-rpygn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vu7-rpygn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:minus-square-fill" {...props}></Icon>
