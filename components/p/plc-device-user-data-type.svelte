<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/udyu9pxgk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="udyu9pxgk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:plc-device-user-data-type" {...props}></Icon>
