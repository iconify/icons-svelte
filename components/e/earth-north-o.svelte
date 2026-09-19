<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/onn0dvxpm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="onn0dvxpm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:earth-north-o" {...props}></Icon>
