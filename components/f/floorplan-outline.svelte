<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ot78e65or.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ot78e65or"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:floorplan-outline" {...props}></Icon>
