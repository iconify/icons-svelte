<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nmq-txbee.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nmq-txbee"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:figma-fill" {...props}></Icon>
