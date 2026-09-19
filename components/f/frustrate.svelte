<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rp_09j-wy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":717,"height":698};
const content = `<path class="rp_09j-wy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:frustrate" {...props}></Icon>
