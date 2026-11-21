<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jnjtaqb5l.css';
import '../../css/z/zogbbpbrk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jnjtaqb5l"/><path class="zogbbpbrk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:hand-right-outline" {...props}></Icon>
