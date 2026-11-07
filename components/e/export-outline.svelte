<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tzryhs1ak.css';
import '../../css/o/on5h-v5us.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tzryhs1ak"/><path class="on5h-v5us"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:export-outline" {...props}></Icon>
