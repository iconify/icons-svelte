<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cpzpu_oja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cpzpu_oja"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:calendar-sync-outline" {...props}></Icon>
