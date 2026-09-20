<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h58-a_tnn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h58-a_tnn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:device-desktop-analytics" {...props}></Icon>
