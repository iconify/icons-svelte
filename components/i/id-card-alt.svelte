<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/focov3bjk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2368,"height":1664};
const content = `<path class="focov3bjk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vs:id-card-alt" {...props}></Icon>
