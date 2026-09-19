<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bzi8fwb-k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bzi8fwb-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:archive" {...props}></Icon>
