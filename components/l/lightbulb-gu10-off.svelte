<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ec4rpzbhn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ec4rpzbhn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:lightbulb-gu10-off" {...props}></Icon>
