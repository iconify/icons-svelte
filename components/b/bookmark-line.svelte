<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kmtk7xb0r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kmtk7xb0r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:bookmark-line" {...props}></Icon>
