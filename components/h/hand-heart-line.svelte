<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a69hfph2s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a69hfph2s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:hand-heart-line" {...props}></Icon>
