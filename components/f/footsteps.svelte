<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mr_t6obzh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="mr_t6obzh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:footsteps" {...props}></Icon>
