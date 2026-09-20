<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w2m2jwb2i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w2m2jwb2i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:bus-2-line" {...props}></Icon>
