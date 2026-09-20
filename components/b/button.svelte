<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lhj3enbnr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="lhj3enbnr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:button" {...props}></Icon>
