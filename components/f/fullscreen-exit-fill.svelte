<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sf9pswoxm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sf9pswoxm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:fullscreen-exit-fill" {...props}></Icon>
