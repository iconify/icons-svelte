<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vqd7_actr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vqd7_actr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:credit-card-check-corner-round" {...props}></Icon>
