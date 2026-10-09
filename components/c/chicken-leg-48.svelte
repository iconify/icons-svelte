<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gtz_8836t.css';
import '../../css/r/rd173ubeg.css';
import '../../css/f/ftbksp_ll.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="gtz_8836t"/><path class="rd173ubeg"/><path class="ftbksp_ll"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chicken-leg-48" {...props}></Icon>
