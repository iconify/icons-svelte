<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zxppngd4j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="zxppngd4j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:eaved-leanto-building-with-fireplace-and-chimney" {...props}></Icon>
