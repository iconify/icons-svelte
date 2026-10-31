<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zpw68zb-y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zpw68zb-y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:diamond-fill-round" {...props}></Icon>
