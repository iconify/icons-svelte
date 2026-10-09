<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g7qx85bwi.css';
import '../../css/j/jcidjcczi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="g7qx85bwi"/><path class="jcidjcczi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:calendar-20-bold" {...props}></Icon>
