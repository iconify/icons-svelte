<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bj5f_ybll.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bj5f_ybll"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:align-horizontal-space-around-sharp" {...props}></Icon>
