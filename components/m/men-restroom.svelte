<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zmuim6abs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zmuim6abs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:men-restroom" {...props}></Icon>
