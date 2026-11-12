<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r31wnti5m.css';
import '../../css/d/d_4d0bbhy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r31wnti5m"/><path class="d_4d0bbhy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:asp-net-core-light" {...props}></Icon>
