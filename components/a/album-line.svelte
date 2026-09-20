<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iso5s1bsk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iso5s1bsk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:album-line" {...props}></Icon>
