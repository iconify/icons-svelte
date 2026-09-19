<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rsl_1urnp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="rsl_1urnp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:close" {...props}></Icon>
