<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-cd4m-xs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q-cd4m-xs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:left-angle-arrow" {...props}></Icon>
