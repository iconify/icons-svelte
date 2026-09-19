<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/owla9ob2z.css';
import '../../css/q/qjd9umv4n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="owla9ob2z"/><path class="qjd9umv4n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:map-unlock" {...props}></Icon>
