<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/me0tyib1r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="me0tyib1r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:phone-off-48" {...props}></Icon>
