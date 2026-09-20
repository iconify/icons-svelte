<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ygt2iabqo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ygt2iabqo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:classify-add-fill" {...props}></Icon>
