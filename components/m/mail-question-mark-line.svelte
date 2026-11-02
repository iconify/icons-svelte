<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/enq9v8bkv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="enq9v8bkv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:mail-question-mark-line" {...props}></Icon>
