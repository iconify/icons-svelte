<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g6_7a0zbx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="g6_7a0zbx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:hang-up-2" {...props}></Icon>
