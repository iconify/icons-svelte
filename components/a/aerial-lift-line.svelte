<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fw0a3jpgs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fw0a3jpgs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:aerial-lift-line" {...props}></Icon>
