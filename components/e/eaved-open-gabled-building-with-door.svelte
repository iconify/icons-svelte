<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yawaon_6c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="yawaon_6c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:eaved-open-gabled-building-with-door" {...props}></Icon>
