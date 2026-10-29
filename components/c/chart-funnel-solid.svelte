<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eruqiz5jz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eruqiz5jz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:chart-funnel-solid" {...props}></Icon>
