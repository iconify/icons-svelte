<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/juz7x9ihj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="juz7x9ihj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:google-buzz-logo" {...props}></Icon>
