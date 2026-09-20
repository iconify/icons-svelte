<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rci0tclox.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rci0tclox"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:city-4-filled" {...props}></Icon>
