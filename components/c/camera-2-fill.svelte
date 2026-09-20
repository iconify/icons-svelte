<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q272urbff.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q272urbff"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:camera-2-fill" {...props}></Icon>
