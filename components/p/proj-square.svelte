<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hu89-tlog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="hu89-tlog"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:proj-square" {...props}></Icon>
