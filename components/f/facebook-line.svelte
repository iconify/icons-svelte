<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nmc74g-ck.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nmc74g-ck"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:facebook-line" {...props}></Icon>
