<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p8cfihbbc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="p8cfihbbc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nimbus:file" {...props}></Icon>
