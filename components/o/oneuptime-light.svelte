<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t00b9jt-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="t00b9jt-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:oneuptime-light" {...props}></Icon>
