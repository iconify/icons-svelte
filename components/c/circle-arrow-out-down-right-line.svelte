<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mhg8a8bde.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mhg8a8bde"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:circle-arrow-out-down-right-line" {...props}></Icon>
