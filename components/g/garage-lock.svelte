<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/la_p4fnuj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="la_p4fnuj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:garage-lock" {...props}></Icon>
