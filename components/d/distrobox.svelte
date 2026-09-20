<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/at0rj4ble.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="at0rj4ble"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:distrobox" {...props}></Icon>
