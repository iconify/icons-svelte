<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ty6or5guf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ty6or5guf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:battery-plus-line" {...props}></Icon>
