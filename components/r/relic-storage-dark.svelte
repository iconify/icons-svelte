<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jwah2sb9a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jwah2sb9a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:relic-storage-dark" {...props}></Icon>
