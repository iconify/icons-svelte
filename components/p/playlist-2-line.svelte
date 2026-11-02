<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sg2gdwbwy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sg2gdwbwy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:playlist-2-line" {...props}></Icon>
