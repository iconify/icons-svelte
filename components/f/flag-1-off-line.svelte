<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zj4z4bhxp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zj4z4bhxp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:flag-1-off-line" {...props}></Icon>
