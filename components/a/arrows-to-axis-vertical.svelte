<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hnn1p_bvo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hnn1p_bvo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:arrows-to-axis-vertical" {...props}></Icon>
