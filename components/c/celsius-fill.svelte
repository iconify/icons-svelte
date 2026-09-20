<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hneyai_ge.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hneyai_ge"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:celsius-fill" {...props}></Icon>
