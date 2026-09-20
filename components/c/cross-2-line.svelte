<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i3bhcgbhw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i3bhcgbhw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:cross-2-line" {...props}></Icon>
