<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lkm6zb_kd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="lkm6zb_kd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:environment-o" {...props}></Icon>
