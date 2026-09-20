<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/geb6cvb1p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="geb6cvb1p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:home-7-line" {...props}></Icon>
