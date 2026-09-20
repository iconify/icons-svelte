<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fz763k3fa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fz763k3fa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:heading-3-line" {...props}></Icon>
