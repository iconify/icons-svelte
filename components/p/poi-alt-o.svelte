<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m6y2cacwd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="m6y2cacwd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:poi-alt-o" {...props}></Icon>
