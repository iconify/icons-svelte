<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y-8ia3bhv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y-8ia3bhv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:merge-cells-horizontal" {...props}></Icon>
