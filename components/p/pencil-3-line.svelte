<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wp3lsl9jd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wp3lsl9jd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:pencil-3-line" {...props}></Icon>
