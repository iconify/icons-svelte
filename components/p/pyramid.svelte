<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sny75bc3q.css';
import '../../css/h/h0-przbga.css';
import '../../css/d/dwuyinbfw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="sny75bc3q"/><path class="h0-przbga"/><path class="dwuyinbfw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:pyramid" {...props}></Icon>
