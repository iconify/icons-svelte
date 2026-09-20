<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t-og94iwn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t-og94iwn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:cookie-fill" {...props}></Icon>
