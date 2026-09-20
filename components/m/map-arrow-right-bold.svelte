<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qcxrfpb3c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qcxrfpb3c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:map-arrow-right-bold" {...props}></Icon>
