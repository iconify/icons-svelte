<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tz12mvlvv.css';
import '../../css/x/xnrsw1b2z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tz12mvlvv"/><path class="xnrsw1b2z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:fish-alt" {...props}></Icon>
