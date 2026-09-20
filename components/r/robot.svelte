<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vqg85fbuk.css';
import '../../css/e/e-sveq-za.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="vqg85fbuk"/><circle class="e-sveq-za"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:robot" {...props}></Icon>
