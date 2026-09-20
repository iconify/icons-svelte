<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fw-0snbeq.css';
import '../../css/z/zxh8vllwu.css';
import '../../css/t/tfwvdwbxo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="fw-0snbeq"/><path class="ouiIcon__fillSecondary zxh8vllwu"/><path class="tfwvdwbxo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:app-console" {...props}></Icon>
