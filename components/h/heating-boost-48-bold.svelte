<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/icg_7_b4w.css';
import '../../css/y/y7lbhg29g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="icg_7_b4w"/><path class="y7lbhg29g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:heating-boost-48-bold" {...props}></Icon>
