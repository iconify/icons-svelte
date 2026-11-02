<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ay5-2y51q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ay5-2y51q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:clipboard-paste-line" {...props}></Icon>
