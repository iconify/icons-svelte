<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b76ej6sry.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b76ej6sry"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:cookie-lock" {...props}></Icon>
