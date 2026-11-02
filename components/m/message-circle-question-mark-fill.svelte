<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zg0obebbm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zg0obebbm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:message-circle-question-mark-fill" {...props}></Icon>
