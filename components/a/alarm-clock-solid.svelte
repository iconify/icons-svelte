<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/szpxu3l4e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="szpxu3l4e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:alarm-clock-solid" {...props}></Icon>
