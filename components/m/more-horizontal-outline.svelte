<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y-nldbc4k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="y-nldbc4k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:more-horizontal-outline" {...props}></Icon>
