<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ochnrrb8e.css';
import '../../css/k/kvj5aub-p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ochnrrb8e"/><path class="kvj5aub-p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:broom-bold" {...props}></Icon>
