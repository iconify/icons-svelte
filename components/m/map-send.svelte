<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c_-c96hat.css';
import '../../css/d/d-y09zibp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="c_-c96hat"/><path class="d-y09zibp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:map-send" {...props}></Icon>
