<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r82pb0bjr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r82pb0bjr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:pot-01" {...props}></Icon>
