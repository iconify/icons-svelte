<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xmhkqlb8i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xmhkqlb8i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:hourglass" {...props}></Icon>
