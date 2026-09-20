<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/byze8w0xj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="byze8w0xj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:google-admob" {...props}></Icon>
