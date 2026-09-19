<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pz5lj8u_t.css';
import '../../css/r/rigcembux.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pz5lj8u_t"/><path class="rigcembux"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-hammer" {...props}></Icon>
