<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r7sr7vyjx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r7sr7vyjx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:flow-display-solid" {...props}></Icon>
