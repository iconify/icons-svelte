<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uo-oketuk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uo-oketuk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:image-refresh-outline" {...props}></Icon>
