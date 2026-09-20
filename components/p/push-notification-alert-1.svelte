<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i2ugmubyk.css';
import '../../css/c/cuvwpsbya.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i2ugmubyk"/><path class="cuvwpsbya"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:push-notification-alert-1" {...props}></Icon>
