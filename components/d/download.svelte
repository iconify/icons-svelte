<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xd189231t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":42,"height":32};
const content = `<path class="xd189231t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="et:download" {...props}></Icon>
