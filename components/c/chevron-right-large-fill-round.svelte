<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h0a7fgn5x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h0a7fgn5x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:chevron-right-large-fill-round" {...props}></Icon>
