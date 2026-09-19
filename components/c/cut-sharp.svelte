<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ko0dg5bwi.css';
import '../../css/d/d70zu1-xi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ko0dg5bwi"/><path class="d70zu1-xi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:cut-sharp" {...props}></Icon>
