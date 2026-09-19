<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d18g1tbcl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="d18g1tbcl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:plane-arrival" {...props}></Icon>
