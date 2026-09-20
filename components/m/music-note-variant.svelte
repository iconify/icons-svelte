<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mo5dze5xl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mo5dze5xl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:music-note-variant" {...props}></Icon>
