<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nlfs0ebmv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nlfs0ebmv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:chart-3d-filled" {...props}></Icon>
