<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t3sqikbxl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t3sqikbxl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:pop-lamp-s" {...props}></Icon>
