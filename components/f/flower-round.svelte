<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hmk-13lct.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hmk-13lct"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:flower-round" {...props}></Icon>
