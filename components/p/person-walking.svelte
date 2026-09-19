<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a40emftlc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="a40emftlc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:person-walking" {...props}></Icon>
