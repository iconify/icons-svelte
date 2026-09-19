<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o14m0cc9r.css';
import '../../css/z/z7gbrqbty.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="o14m0cc9r"/><path class="z7gbrqbty"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:pricetag-multiple" {...props}></Icon>
