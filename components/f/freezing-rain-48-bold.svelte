<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vzc0f4bbg.css';
import '../../css/d/d6nu3aclr.css';
import '../../css/m/mky7hybil.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vzc0f4bbg"/><path class="d6nu3aclr"/><path class="mky7hybil"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:freezing-rain-48-bold" {...props}></Icon>
