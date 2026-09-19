<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qlmn_lbrb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qlmn_lbrb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:gopuram" {...props}></Icon>
