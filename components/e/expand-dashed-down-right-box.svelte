<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vs3b2pbzq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vs3b2pbzq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:expand-dashed-down-right-box" {...props}></Icon>
