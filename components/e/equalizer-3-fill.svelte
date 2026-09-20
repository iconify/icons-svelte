<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ahvhl-yox.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ahvhl-yox"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:equalizer-3-fill" {...props}></Icon>
