<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s8g_54abo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="s8g_54abo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:baby" {...props}></Icon>
