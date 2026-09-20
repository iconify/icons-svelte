<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b4qr7wbws.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="b4qr7wbws"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:connections-settings" {...props}></Icon>
