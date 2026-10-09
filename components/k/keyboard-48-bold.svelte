<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qu9rvubvf.css';
import '../../css/e/egkzj7bkm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="qu9rvubvf"/><path class="egkzj7bkm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:keyboard-48-bold" {...props}></Icon>
