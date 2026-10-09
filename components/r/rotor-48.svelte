<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i5i-ymejz.css';
import '../../css/x/xv-3bjb_h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="i5i-ymejz"/><path class="xv-3bjb_h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:rotor-48" {...props}></Icon>
