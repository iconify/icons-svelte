<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lwyqp9jxs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lwyqp9jxs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:layers-minus" {...props}></Icon>
