<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wt57vq-0m.css';
import '../../css/z/zlx_zlb4h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wt57vq-0m"/><path class="zlx_zlb4h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:battery-full-sharp" {...props}></Icon>
