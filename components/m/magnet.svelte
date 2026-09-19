<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pwdw3u4am.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="pwdw3u4am"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:magnet" {...props}></Icon>
