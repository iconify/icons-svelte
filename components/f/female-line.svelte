<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z-lrk1cyk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z-lrk1cyk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:female-line" {...props}></Icon>
