<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/epozpjb4m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="epozpjb4m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:delete-keyboard" {...props}></Icon>
