<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lea21cbgo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lea21cbgo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:lamp-wall-down-line" {...props}></Icon>
