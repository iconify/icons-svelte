<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ubb0mibui.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ubb0mibui"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:double-caret-left-circle-outline" {...props}></Icon>
