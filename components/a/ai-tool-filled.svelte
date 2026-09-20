<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a1drfsbhs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a1drfsbhs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:ai-tool-filled" {...props}></Icon>
