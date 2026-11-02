<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/msldd0l0u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="msldd0l0u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:flight-land-fill" {...props}></Icon>
