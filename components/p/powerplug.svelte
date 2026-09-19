<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xy6ce7bis.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":896,"height":1024};
const content = `<path class="xy6ce7bis"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:powerplug" {...props}></Icon>
