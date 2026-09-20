<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cbqfrhbgu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="cbqfrhbgu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:connector-type-1" {...props}></Icon>
