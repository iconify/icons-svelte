<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fp36jgbxh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="fp36jgbxh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:dashboard-3" {...props}></Icon>
