<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hwyr5yfgi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hwyr5yfgi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:bell-plus-fill" {...props}></Icon>
