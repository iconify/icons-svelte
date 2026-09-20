<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vcd4a1t7h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vcd4a1t7h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:blackberry-logo-bold" {...props}></Icon>
