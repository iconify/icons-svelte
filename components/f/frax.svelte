<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jf12py5gn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jf12py5gn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:frax" {...props}></Icon>
