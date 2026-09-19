<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fja-axsxo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="fja-axsxo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:campaign-monitor" {...props}></Icon>
