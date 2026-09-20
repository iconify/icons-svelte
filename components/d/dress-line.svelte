<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l4e3u-brz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l4e3u-brz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:dress-line" {...props}></Icon>
