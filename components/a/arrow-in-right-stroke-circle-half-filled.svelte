<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wl5wj4bmg.css';
import '../../css/j/jgmlxzbvj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wl5wj4bmg"/><path class="jgmlxzbvj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-in-right-stroke-circle-half-filled" {...props}></Icon>
