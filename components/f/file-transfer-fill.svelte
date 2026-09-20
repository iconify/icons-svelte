<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qwtzf7nop.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qwtzf7nop"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:file-transfer-fill" {...props}></Icon>
