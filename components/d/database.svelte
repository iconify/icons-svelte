<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x0l8s-b2r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="x0l8s-b2r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:database" {...props}></Icon>
