<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d8j44qm-v.css';
import '../../css/q/q7zl1sbxo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="d8j44qm-v"/><path class="q7zl1sbxo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:rivet-48-bold" {...props}></Icon>
