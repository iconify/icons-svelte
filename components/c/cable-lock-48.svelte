<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ovlsupbow.css';
import '../../css/e/ep-e4lbdz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ovlsupbow"/><path class="ep-e4lbdz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cable-lock-48" {...props}></Icon>
