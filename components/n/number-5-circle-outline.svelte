<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f_8x70c2s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f_8x70c2s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:number-5-circle-outline" {...props}></Icon>
