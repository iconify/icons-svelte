<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hks2i43dl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hks2i43dl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:passport-fill-round" {...props}></Icon>
