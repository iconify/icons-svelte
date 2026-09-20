<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i7vihh02o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i7vihh02o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:download-line" {...props}></Icon>
