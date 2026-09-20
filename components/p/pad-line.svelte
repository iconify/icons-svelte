<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jk0cdlith.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jk0cdlith"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:pad-line" {...props}></Icon>
