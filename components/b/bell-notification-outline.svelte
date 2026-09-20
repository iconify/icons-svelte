<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sb6ctrb9b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sb6ctrb9b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:bell-notification-outline" {...props}></Icon>
