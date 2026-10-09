<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vt5zfkb5n.css';
import '../../css/k/kx34z-i_j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="vt5zfkb5n"/><path class="kx34z-i_j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:heat-battery-20" {...props}></Icon>
