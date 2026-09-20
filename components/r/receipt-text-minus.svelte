<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jpc5t2beq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jpc5t2beq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:receipt-text-minus" {...props}></Icon>
