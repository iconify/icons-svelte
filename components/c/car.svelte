<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t0334b8lh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":448};
const content = `<path class="t0334b8lh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:car" {...props}></Icon>
