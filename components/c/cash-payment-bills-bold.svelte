<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vbx7cjb1m.css';
import '../../css/a/a19jmacmq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vbx7cjb1m"/><path class="a19jmacmq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:cash-payment-bills-bold" {...props}></Icon>
