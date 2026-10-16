<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m7tl1ob_w.css';
import '../../css/g/gdz_w_6os.css';
import '../../css/c/c65-ehvfy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="m7tl1ob_w"/><path class="gdz_w_6os"/><path class="c65-ehvfy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:gas-sphere-48" {...props}></Icon>
