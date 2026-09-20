<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nl7qs61zc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nl7qs61zc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:robot-vacuum-variant-alert" {...props}></Icon>
