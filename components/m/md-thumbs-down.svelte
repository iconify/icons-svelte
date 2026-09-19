<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a1jo94x0n.css';
import '../../css/h/h1tlzyagf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="a1jo94x0n"/><path class="h1tlzyagf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-thumbs-down" {...props}></Icon>
