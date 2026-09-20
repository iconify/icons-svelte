<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yef1ulbhf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yef1ulbhf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:alert-bell-notification-2" {...props}></Icon>
