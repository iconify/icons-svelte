<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p068o5acv.css';
import '../../css/f/f-iag6myh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p068o5acv"/><path class="f-iag6myh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:pic-line" {...props}></Icon>
