<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cw0_76buw.css';
import '../../css/d/d22vebp3d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="cw0_76buw"/><path class="d22vebp3d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cargo-ship-48" {...props}></Icon>
