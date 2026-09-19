<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z_xre-9eh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z_xre-9eh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:plane" {...props}></Icon>
