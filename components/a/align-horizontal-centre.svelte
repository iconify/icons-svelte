<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i82zxjp8v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i82zxjp8v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:align-horizontal-centre" {...props}></Icon>
