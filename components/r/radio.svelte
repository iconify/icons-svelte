<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wff3039xb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":456};
const content = `<path class="wff3039xb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:radio" {...props}></Icon>
