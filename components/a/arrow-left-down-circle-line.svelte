<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ialpt6mul.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ialpt6mul"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:arrow-left-down-circle-line" {...props}></Icon>
