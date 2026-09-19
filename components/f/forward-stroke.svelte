<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vaqkg9bhj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vaqkg9bhj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:forward-stroke" {...props}></Icon>
