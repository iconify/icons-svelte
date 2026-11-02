<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w9gasub-a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w9gasub-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:markdown-line" {...props}></Icon>
