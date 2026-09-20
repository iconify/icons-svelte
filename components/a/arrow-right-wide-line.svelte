<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z6-_visne.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z6-_visne"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:arrow-right-wide-line" {...props}></Icon>
