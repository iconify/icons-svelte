<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x8e-izr_t.css';
import '../../css/f/fxil81qql.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="x8e-izr_t"/><path class="fxil81qql"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:battery-pouch-48" {...props}></Icon>
