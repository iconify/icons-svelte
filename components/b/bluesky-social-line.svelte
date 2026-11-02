<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/saw8j727d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="saw8j727d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:bluesky-social-line" {...props}></Icon>
