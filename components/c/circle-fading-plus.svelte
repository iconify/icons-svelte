<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ec4i1g93h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ec4i1g93h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:circle-fading-plus" {...props}></Icon>
