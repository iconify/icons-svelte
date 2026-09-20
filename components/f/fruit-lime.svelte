<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/unpu3551h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="unpu3551h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:fruit-lime" {...props}></Icon>
