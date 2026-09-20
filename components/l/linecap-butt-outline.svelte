<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o44ucuj-r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="o44ucuj-r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:linecap-butt-outline" {...props}></Icon>
