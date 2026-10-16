<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e0bb00b5y.css';
import '../../css/q/q5bh6acin.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="e0bb00b5y"/><path class="q5bh6acin"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:pipe-insulation-48-bold" {...props}></Icon>
