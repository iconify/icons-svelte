<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/srl88obkl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="srl88obkl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:peace" {...props}></Icon>
