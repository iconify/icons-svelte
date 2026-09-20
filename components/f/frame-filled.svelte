<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dvm4ysb3i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dvm4ysb3i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:frame-filled" {...props}></Icon>
