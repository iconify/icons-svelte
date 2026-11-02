<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mq8hgf16d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mq8hgf16d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:badge-question-mark-fill" {...props}></Icon>
