<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fpv90mrgo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fpv90mrgo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:bone-off" {...props}></Icon>
