<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e142afbbv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="e142afbbv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:hand-cursor-flat" {...props}></Icon>
