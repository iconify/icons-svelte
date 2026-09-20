<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l_de38b0p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="l_de38b0p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:arrow-left-from-rectangle-tall-outline" {...props}></Icon>
