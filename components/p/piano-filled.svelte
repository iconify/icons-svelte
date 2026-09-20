<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n0a9c_ain.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n0a9c_ain"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:piano-filled" {...props}></Icon>
