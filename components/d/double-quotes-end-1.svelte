<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gwydrwbld.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path class="gwydrwbld"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:double-quotes-end-1" {...props}></Icon>
