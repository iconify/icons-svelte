<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pmtm5li5d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pmtm5li5d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:marpui-light" {...props}></Icon>
