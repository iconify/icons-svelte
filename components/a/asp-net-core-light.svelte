<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r31wnti5m.css';
import '../../css/i/i5za_y8px.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r31wnti5m"/><path class="i5za_y8px"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:asp-net-core-light" {...props}></Icon>
