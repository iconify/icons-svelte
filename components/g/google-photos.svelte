<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ag5wjrrnf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ag5wjrrnf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:google-photos" {...props}></Icon>
