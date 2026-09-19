<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hojzm4bji.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hojzm4bji"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:arrow-thick-from-top" {...props}></Icon>
