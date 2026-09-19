<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y49sr1xcb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="y49sr1xcb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:drawing-compass" {...props}></Icon>
