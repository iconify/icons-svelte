<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rgrj4e4gu.css';
import '../../css/x/xpheglbff.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rgrj4e4gu"/><path class="xpheglbff"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:koito" {...props}></Icon>
