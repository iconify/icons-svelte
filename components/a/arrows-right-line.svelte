<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k2dkhx_uu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k2dkhx_uu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:arrows-right-line" {...props}></Icon>
