<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fxw22obcs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fxw22obcs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:credit-card-close-corner-round" {...props}></Icon>
