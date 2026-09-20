<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vgl-t-b-k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vgl-t-b-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:equal" {...props}></Icon>
