<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qwq3i_b2s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qwq3i_b2s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:currency-gtq" {...props}></Icon>
