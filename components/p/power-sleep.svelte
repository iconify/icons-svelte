<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zrazbb12a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zrazbb12a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:power-sleep" {...props}></Icon>
