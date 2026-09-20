<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x-dmelbmt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="x-dmelbmt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:horizontal-ladder" {...props}></Icon>
