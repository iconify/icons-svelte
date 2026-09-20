<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mpknhhbne.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mpknhhbne"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:chart-bubble" {...props}></Icon>
