<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xb0atybhd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xb0atybhd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:chevrons-left" {...props}></Icon>
