<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r60oz_agq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r60oz_agq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:chequebook-arrow-right" {...props}></Icon>
