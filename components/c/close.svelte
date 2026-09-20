<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qtk-kuxcr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qtk-kuxcr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:close" {...props}></Icon>
