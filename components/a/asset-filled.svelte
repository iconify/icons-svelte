<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l7pi4cqiq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l7pi4cqiq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:asset-filled" {...props}></Icon>
