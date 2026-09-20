<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w-ff33bdj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w-ff33bdj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:device-mobile-pin" {...props}></Icon>
