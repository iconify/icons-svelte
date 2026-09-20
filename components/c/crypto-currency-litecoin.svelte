<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gcehwxpiv.css';
import '../../css/q/qs3nn1ykv.css';
import '../../css/o/o3v08d-1q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gcehwxpiv"/><path class="qs3nn1ykv"/><path class="o3v08d-1q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:crypto-currency-litecoin" {...props}></Icon>
