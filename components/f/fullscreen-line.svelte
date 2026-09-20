<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pmez0ebck.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pmez0ebck"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:fullscreen-line" {...props}></Icon>
