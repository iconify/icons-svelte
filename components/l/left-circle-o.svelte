<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i4pu07bda.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="i4pu07bda"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:left-circle-o" {...props}></Icon>
