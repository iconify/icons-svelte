<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vmy6o3vyt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vmy6o3vyt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:bulb-sparkle-fill-round" {...props}></Icon>
