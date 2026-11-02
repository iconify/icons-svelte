<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ztgj2k7_i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ztgj2k7_i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:parking-lights-line" {...props}></Icon>
