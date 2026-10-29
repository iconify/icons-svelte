<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lfxe5-btc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lfxe5-btc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:circle-arrow-right-solid" {...props}></Icon>
