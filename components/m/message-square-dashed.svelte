<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lcmoi-m3x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lcmoi-m3x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:message-square-dashed" {...props}></Icon>
