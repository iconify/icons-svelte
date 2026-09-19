<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e5j33dbsp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e5j33dbsp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:cable-car-filled" {...props}></Icon>
