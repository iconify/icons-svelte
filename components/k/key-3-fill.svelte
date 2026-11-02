<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sxjebjbiu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sxjebjbiu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:key-3-fill" {...props}></Icon>
