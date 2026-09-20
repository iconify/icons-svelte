<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rhyy_4bdf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rhyy_4bdf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:crystal-ball-fill" {...props}></Icon>
