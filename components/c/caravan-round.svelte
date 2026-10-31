<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g86woor3h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g86woor3h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:caravan-round" {...props}></Icon>
