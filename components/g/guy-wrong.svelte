<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zxjac9qul.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zxjac9qul"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:guy-wrong" {...props}></Icon>
