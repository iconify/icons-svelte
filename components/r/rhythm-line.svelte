<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pp641cc6p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pp641cc6p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:rhythm-line" {...props}></Icon>
