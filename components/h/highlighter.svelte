<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tfm243b6p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tfm243b6p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:highlighter" {...props}></Icon>
