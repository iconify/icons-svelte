<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x40gnkblj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x40gnkblj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:panorama-horizontal-off" {...props}></Icon>
