<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/meymu9b3o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="meymu9b3o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:eye-hide-fill-16" {...props}></Icon>
