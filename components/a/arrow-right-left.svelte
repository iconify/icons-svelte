<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vlwa5nbcn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vlwa5nbcn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:arrow-right-left" {...props}></Icon>
