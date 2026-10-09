<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mwduy1bns.css';
import '../../css/k/kuz80_b7w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="mwduy1bns"/><path class="kuz80_b7w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bold-48-bold" {...props}></Icon>
