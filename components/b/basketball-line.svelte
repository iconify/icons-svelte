<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qr3roy_bu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qr3roy_bu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:basketball-line" {...props}></Icon>
