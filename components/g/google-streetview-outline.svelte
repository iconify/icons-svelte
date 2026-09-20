<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h38u9um-k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="h38u9um-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:google-streetview-outline" {...props}></Icon>
