<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rrfsx9kxr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="rrfsx9kxr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:key-remix" {...props}></Icon>
