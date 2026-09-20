<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ooh1spb_e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ooh1spb_e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:numeric-9-circle-outline" {...props}></Icon>
