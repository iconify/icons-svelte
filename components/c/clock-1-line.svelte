<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iqb9lzyli.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iqb9lzyli"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:clock-1-line" {...props}></Icon>
