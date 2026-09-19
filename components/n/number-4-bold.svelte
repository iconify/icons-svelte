<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/saxk2_e7o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="saxk2_e7o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:number-4-bold" {...props}></Icon>
