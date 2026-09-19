<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yfr3wiw7h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":768,"height":1024};
const content = `<path class="yfr3wiw7h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:braillefour" {...props}></Icon>
