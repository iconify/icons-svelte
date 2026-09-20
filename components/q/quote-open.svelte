<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mrzv21b6h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mrzv21b6h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:quote-open" {...props}></Icon>
