<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z25mhhbdl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z25mhhbdl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:distribute-horizontal-right" {...props}></Icon>
