<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fg7ralbba.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="fg7ralbba"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:gear-compact" {...props}></Icon>
