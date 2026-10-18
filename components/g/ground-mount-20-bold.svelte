<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rkqr1j59e.css';
import '../../css/g/gx519cbvi.css';
import '../../css/y/yv842m9yr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="rkqr1j59e"/><path class="gx519cbvi"/><path class="yv842m9yr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ground-mount-20-bold" {...props}></Icon>
