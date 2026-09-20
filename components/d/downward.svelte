<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/shfcvx8wr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<path class="shfcvx8wr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:downward" {...props}></Icon>
