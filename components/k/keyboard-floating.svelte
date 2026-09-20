<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/txgjokbzb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="txgjokbzb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:keyboard-floating" {...props}></Icon>
