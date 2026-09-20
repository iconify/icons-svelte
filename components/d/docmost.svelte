<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sfumhs5dd.css';
import '../../css/n/nsh88-uyo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sfumhs5dd"/><path class="nsh88-uyo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:docmost" {...props}></Icon>
