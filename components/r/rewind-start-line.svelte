<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/blw-k0btf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="blw-k0btf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:rewind-start-line" {...props}></Icon>
