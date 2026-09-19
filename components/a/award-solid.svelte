<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dsi1s7btx.css';
import '../../css/n/nhkex-b_o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dsi1s7btx"/><path clip-rule="evenodd" class="nhkex-b_o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:award-solid" {...props}></Icon>
