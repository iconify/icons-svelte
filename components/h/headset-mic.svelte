<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aw6f8ebgz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":480};
const content = `<path class="aw6f8ebgz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:headset-mic" {...props}></Icon>
