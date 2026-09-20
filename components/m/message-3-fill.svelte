<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k17b8osvx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k17b8osvx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:message-3-fill" {...props}></Icon>
