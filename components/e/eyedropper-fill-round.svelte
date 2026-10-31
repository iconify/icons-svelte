<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b0zj1p-mn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b0zj1p-mn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:eyedropper-fill-round" {...props}></Icon>
