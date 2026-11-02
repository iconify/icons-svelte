<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xce7e9krf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xce7e9krf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:question-2-line" {...props}></Icon>
