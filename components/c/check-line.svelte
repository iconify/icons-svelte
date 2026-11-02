<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fas7ocjry.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fas7ocjry"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:check-line" {...props}></Icon>
