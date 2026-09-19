<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d8fiu01er.css';
import '../../css/x/xpeiq2kly.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="d8fiu01er"/><path class="xpeiq2kly"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:map-star" {...props}></Icon>
