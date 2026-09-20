<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/afdx_obcn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="afdx_obcn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:lightbulb-group-off-outline" {...props}></Icon>
