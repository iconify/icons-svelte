<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ua8c-eb0e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="ua8c-eb0e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:pen" {...props}></Icon>
