<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jxw75molp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jxw75molp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:exit-outline" {...props}></Icon>
