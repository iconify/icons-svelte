<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sr9vg-bzb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sr9vg-bzb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:arrow-down-rhombus" {...props}></Icon>
