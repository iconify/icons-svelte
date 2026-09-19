<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pjp5kfbwt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="pjp5kfbwt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:history" {...props}></Icon>
