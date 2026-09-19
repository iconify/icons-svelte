<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/por8_p__f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="por8_p__f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:bus-alt" {...props}></Icon>
