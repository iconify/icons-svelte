<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vto2pjblt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="vto2pjblt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="formkit:repeater" {...props}></Icon>
