<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lznn-3o3r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lznn-3o3r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:hairdresser" {...props}></Icon>
