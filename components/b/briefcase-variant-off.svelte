<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eb4kb1uwx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eb4kb1uwx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:briefcase-variant-off" {...props}></Icon>
