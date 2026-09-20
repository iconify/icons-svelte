<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xmdn0hbjl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="xmdn0hbjl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-walking-bicycle" {...props}></Icon>
