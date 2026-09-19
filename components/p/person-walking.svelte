<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pv1kbccre.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":320,"height":512};
const content = `<path class="pv1kbccre"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:person-walking" {...props}></Icon>
