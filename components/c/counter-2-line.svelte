<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kkpb6dbuc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kkpb6dbuc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:counter-2-line" {...props}></Icon>
