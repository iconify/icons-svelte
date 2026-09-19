<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mxe_zphpb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="mxe_zphpb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:arrow-down-square" {...props}></Icon>
