<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lytj4i0za.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lytj4i0za"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:plugin-2-fill" {...props}></Icon>
