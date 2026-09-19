<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x1e-a9n7j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="x1e-a9n7j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:building-circle-exclamation" {...props}></Icon>
