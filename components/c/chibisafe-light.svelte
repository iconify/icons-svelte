<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fagntxw4g.css';
import '../../css/t/tqmas5pkf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fagntxw4g"/><path class="tqmas5pkf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:chibisafe-light" {...props}></Icon>
