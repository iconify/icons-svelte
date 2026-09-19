<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qpslu009k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qpslu009k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:arrow-data-transfer-horizontal" {...props}></Icon>
