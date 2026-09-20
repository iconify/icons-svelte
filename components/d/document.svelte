<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tiwb4upak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tiwb4upak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:document" {...props}></Icon>
