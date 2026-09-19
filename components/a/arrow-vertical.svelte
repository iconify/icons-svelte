<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ri_arhbfk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ri_arhbfk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:arrow-vertical" {...props}></Icon>
