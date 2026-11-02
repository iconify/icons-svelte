<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ly5yssbjv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ly5yssbjv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:book-audio-fill" {...props}></Icon>
