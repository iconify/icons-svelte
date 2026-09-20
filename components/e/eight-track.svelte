<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b17ogtb1x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b17ogtb1x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:eight-track" {...props}></Icon>
