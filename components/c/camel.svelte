<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bmy4l5bds.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2016,"height":1664};
const content = `<path class="bmy4l5bds"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vs:camel" {...props}></Icon>
