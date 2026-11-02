<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jhau-5bid.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jhau-5bid"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:cast-line" {...props}></Icon>
