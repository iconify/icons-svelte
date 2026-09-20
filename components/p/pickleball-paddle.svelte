<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/am0biv4xa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="am0biv4xa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:pickleball-paddle" {...props}></Icon>
