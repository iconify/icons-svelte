<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mez3sq6az.css';
import '../../css/f/f5mgz9qau.css';
import '../../css/i/in0d74b0s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="mez3sq6az"/><path class="f5mgz9qau"/><path class="in0d74b0s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:archery-48" {...props}></Icon>
