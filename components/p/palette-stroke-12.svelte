<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wu_10h8-w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="wu_10h8-w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:palette-stroke-12" {...props}></Icon>
