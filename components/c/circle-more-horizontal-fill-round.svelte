<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q26luwbrv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q26luwbrv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:circle-more-horizontal-fill-round" {...props}></Icon>
