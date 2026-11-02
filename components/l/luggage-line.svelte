<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c7nx_8j1e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c7nx_8j1e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:luggage-line" {...props}></Icon>
