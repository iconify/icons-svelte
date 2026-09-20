<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/df2i0cbrv.css';
import '../../css/m/m0c34ebvb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="df2i0cbrv"/><path clip-rule="evenodd" class="m0c34ebvb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nextcloud-office-light" {...props}></Icon>
