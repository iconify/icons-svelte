<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gbsysm48b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gbsysm48b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:conduit-dark" {...props}></Icon>
