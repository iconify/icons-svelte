<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/us89vp96s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="us89vp96s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:play-circle-fill" {...props}></Icon>
