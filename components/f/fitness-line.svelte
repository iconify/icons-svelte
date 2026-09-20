<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pn_yhzzwo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pn_yhzzwo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:fitness-line" {...props}></Icon>
