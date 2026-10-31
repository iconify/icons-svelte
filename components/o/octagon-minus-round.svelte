<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ibtrv19_w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ibtrv19_w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:octagon-minus-round" {...props}></Icon>
