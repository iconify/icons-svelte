<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wbf2j5b6e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="wbf2j5b6e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:q" {...props}></Icon>
