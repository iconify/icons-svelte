<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lvp8xachq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lvp8xachq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:cashless-payment-online-statement-monitor-bold" {...props}></Icon>
