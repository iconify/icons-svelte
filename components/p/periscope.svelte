<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k11sssg2e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k11sssg2e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:periscope" {...props}></Icon>
