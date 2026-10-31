<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x1w9f06fm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x1w9f06fm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:desktop-round" {...props}></Icon>
