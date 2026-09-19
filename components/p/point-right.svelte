<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w541gs4bu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="w541gs4bu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:point-right" {...props}></Icon>
