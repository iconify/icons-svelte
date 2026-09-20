<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yv6mthbny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yv6mthbny"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:kred" {...props}></Icon>
