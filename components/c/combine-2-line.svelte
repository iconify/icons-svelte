<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-e5hmj2z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m-e5hmj2z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:combine-2-line" {...props}></Icon>
