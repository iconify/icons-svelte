<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d8hsnibud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="d8hsnibud"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:layout-window-8" {...props}></Icon>
