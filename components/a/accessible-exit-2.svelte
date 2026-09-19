<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dw80_35gc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dw80_35gc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:accessible-exit-2" {...props}></Icon>
