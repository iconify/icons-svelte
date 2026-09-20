<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qamy95zgq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qamy95zgq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:dog-side" {...props}></Icon>
