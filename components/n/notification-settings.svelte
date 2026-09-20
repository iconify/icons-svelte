<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mk5t21bgc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mk5t21bgc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:notification-settings" {...props}></Icon>
