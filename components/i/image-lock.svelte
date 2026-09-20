<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/efv4qke4y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="efv4qke4y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:image-lock" {...props}></Icon>
