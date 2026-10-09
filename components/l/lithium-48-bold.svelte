<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/omdaj5bmv.css';
import '../../css/f/fphpswbyz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="omdaj5bmv"/><path class="fphpswbyz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:lithium-48-bold" {...props}></Icon>
