<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kr30rzbwx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kr30rzbwx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:border-radius-line" {...props}></Icon>
