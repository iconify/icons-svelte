<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zcc7ulb6x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zcc7ulb6x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:moment-line" {...props}></Icon>
