<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bhkq8cbdm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="bhkq8cbdm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:pixel-gasoline-pump" {...props}></Icon>
