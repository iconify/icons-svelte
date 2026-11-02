<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zz4x-hbzt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zz4x-hbzt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:receive-money-fill" {...props}></Icon>
