<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c9_h_1bua.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c9_h_1bua"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:google-play" {...props}></Icon>
