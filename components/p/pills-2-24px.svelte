<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tgobnwbdc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tgobnwbdc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:pills-2-24px" {...props}></Icon>
