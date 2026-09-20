<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/snce60dbv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="snce60dbv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:multiselect-line" {...props}></Icon>
