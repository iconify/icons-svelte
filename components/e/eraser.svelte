<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i50zk7duk.css';
import '../../css/a/a_3ga6bbw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="i50zk7duk"/><path class="a_3ga6bbw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:eraser" {...props}></Icon>
