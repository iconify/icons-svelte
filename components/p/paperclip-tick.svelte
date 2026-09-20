<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uguz04bll.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uguz04bll"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:paperclip-tick" {...props}></Icon>
