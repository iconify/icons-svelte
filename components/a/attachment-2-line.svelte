<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tx742i41n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tx742i41n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:attachment-2-line" {...props}></Icon>
