<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/guacuabyw.css';
import '../../css/w/wqgx4hy9o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="guacuabyw"/><path class="wqgx4hy9o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:open-door-line" {...props}></Icon>
