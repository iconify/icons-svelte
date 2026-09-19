<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p1_rj_2ly.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p1_rj_2ly"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:adjustments-horizontal-solid" {...props}></Icon>
