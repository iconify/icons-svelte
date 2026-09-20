<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-21qrbsi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="m-21qrbsi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:ringing-bell-notification-solid" {...props}></Icon>
