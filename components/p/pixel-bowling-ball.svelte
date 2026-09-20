<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0alzsjun.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="a0alzsjun"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:pixel-bowling-ball" {...props}></Icon>
