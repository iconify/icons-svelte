<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ysul9tm-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ysul9tm-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:clock-out-fill-16" {...props}></Icon>
