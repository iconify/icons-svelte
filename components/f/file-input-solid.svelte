<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w4s8tgwzx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w4s8tgwzx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:file-input-solid" {...props}></Icon>
