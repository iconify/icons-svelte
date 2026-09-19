<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bwwf7kgie.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="bwwf7kgie"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:creative-commons-remix" {...props}></Icon>
