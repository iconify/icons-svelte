<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l1j29iy8v.css';
import '../../css/g/gljfs3bti.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="l1j29iy8v"/><path class="gljfs3bti"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:eye-closed-20" {...props}></Icon>
