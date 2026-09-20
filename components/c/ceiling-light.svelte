<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gs6656bhq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gs6656bhq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:ceiling-light" {...props}></Icon>
