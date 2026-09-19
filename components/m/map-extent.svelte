<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j7l3pbb-c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="j7l3pbb-c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:map-extent" {...props}></Icon>
