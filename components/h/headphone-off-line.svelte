<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xx63evk1q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xx63evk1q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:headphone-off-line" {...props}></Icon>
