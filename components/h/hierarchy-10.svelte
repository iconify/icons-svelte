<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yfbdei4yb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="yfbdei4yb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:hierarchy-10" {...props}></Icon>
