<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-4mr4ruq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q-4mr4ruq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:earth-2-line" {...props}></Icon>
