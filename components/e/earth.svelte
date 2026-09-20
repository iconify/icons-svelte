<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pbl41hxck.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pbl41hxck"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:earth" {...props}></Icon>
