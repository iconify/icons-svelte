<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b26kvl1wt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b26kvl1wt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:robot-line" {...props}></Icon>
