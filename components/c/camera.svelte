<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zvt-etbdx.css';
import '../../css/s/sh3jq6b7q.css';
import '../../css/g/gr0sanbkg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="zvt-etbdx"/><path class="sh3jq6b7q"/><ellipse class="gr0sanbkg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nimbus:camera" {...props}></Icon>
