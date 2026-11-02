<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j6s1nv7sx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j6s1nv7sx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:diamond-percent-line" {...props}></Icon>
