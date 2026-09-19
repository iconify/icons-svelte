<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o7f1umbwh.css';
import '../../css/e/e1yonmpfk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="o7f1umbwh"/><path class="e1yonmpfk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:map-tags" {...props}></Icon>
