<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ppom3knrm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="ppom3knrm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:less-than" {...props}></Icon>
