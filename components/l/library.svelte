<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zs8_lbz1a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zs8_lbz1a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:library" {...props}></Icon>
