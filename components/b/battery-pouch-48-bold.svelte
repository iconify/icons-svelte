<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e8r7dteuj.css';
import '../../css/s/sktgnkdka.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="e8r7dteuj"/><path class="sktgnkdka"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:battery-pouch-48-bold" {...props}></Icon>
