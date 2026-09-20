<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h50gsac4i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h50gsac4i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:battery-lock-open" {...props}></Icon>
