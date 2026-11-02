<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m24q4o26z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m24q4o26z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:boom-box-fill" {...props}></Icon>
