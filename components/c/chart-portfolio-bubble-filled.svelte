<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xhn4pvblz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xhn4pvblz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:chart-portfolio-bubble-filled" {...props}></Icon>
