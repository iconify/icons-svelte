<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ux-84ebfj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ux-84ebfj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:dice-five" {...props}></Icon>
