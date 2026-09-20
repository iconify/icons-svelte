<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gkqybcbiz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gkqybcbiz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:lightbulb-shine-line" {...props}></Icon>
