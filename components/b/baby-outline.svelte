<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r4sfmobcd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="r4sfmobcd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:baby-outline" {...props}></Icon>
