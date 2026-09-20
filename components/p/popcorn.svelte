<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/twu4h7bor.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="twu4h7bor"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:popcorn" {...props}></Icon>
