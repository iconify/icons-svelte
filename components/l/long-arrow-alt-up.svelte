<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c7ij-6bcu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":512};
const content = `<path class="c7ij-6bcu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:long-arrow-alt-up" {...props}></Icon>
