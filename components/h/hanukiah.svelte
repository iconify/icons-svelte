<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d48fz7ajf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="d48fz7ajf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:hanukiah" {...props}></Icon>
