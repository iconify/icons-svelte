<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y7i9mubje.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="y7i9mubje"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:asleep" {...props}></Icon>
