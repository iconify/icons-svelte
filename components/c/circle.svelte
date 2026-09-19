<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/ba61gnnld.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ba61gnnld"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:circle" {...props}></Icon>
