<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t24wsexbe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t24wsexbe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:proxy-auto-outline" {...props}></Icon>
