<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/khnu7pbkf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="khnu7pbkf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:ingots" {...props}></Icon>
