<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g6a4mhboy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g6a4mhboy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:pingpong-fill" {...props}></Icon>
