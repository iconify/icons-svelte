<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hblpo_btx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hblpo_btx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:gradienter-fill" {...props}></Icon>
