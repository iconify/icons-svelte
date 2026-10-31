<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hl0ktuiwc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hl0ktuiwc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:bear-round" {...props}></Icon>
