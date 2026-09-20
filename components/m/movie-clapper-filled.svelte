<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jxzy3ubzk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jxzy3ubzk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:movie-clapper-filled" {...props}></Icon>
