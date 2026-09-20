<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ugn-a1bzd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ugn-a1bzd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:flip-horizontal-2-line" {...props}></Icon>
