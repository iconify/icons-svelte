<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aqtqnojkt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aqtqnojkt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:desktop-tower-round" {...props}></Icon>
