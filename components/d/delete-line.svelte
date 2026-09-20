<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zt2cw3b-j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zt2cw3b-j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:delete-line" {...props}></Icon>
