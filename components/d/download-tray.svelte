<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dx8akr0rj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="dx8akr0rj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:download-tray" {...props}></Icon>
