<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c2d12ibxs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c2d12ibxs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:foggy-line" {...props}></Icon>
