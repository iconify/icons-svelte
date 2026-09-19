<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/epgk7ub8d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="epgk7ub8d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:cogs" {...props}></Icon>
