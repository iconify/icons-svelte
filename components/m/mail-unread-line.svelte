<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/otoo-_9fi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="otoo-_9fi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:mail-unread-line" {...props}></Icon>
