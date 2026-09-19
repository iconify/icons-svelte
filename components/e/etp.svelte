<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qygi0x8_o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="qygi0x8_o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:etp" {...props}></Icon>
