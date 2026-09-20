<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/re4fspsiq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="re4fspsiq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:facebook-1-solid" {...props}></Icon>
