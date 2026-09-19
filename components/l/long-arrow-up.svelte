<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d-j3llfvp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="d-j3llfvp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:long-arrow-up" {...props}></Icon>
