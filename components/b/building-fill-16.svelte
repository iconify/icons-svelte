<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sym2kf7vy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="sym2kf7vy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:building-fill-16" {...props}></Icon>
