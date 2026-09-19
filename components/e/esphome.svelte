<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t88ywcbrq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t88ywcbrq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:esphome" {...props}></Icon>
