<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nwn9qcb9d.css';
import '../../css/l/lpk12-20r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nwn9qcb9d"/><path class="lpk12-20r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:lufin" {...props}></Icon>
