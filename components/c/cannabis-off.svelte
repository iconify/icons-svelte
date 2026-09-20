<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i08h9r8xw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i08h9r8xw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:cannabis-off" {...props}></Icon>
