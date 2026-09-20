<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jskr7fbld.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="jskr7fbld"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:microscope" {...props}></Icon>
