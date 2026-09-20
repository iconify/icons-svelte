<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b8f83c8eh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b8f83c8eh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:credit-card-icc-chip" {...props}></Icon>
