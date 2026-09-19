<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y0397_6ub.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="y0397_6ub"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:ideal" {...props}></Icon>
