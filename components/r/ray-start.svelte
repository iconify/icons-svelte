<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/at84-bcot.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="at84-bcot"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:ray-start" {...props}></Icon>
