<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jyd2g7b-t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="jyd2g7b-t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nimbus:chevron-down" {...props}></Icon>
