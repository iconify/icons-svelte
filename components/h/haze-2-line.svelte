<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l0ewowbic.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l0ewowbic"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:haze-2-line" {...props}></Icon>
