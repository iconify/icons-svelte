<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eeq8ggb4k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eeq8ggb4k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:arrow-left-up-circle-line" {...props}></Icon>
