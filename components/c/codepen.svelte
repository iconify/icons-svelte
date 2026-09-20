<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l1q7olbag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l1q7olbag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:codepen" {...props}></Icon>
