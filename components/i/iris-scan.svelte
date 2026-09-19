<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oiwv8_cbo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oiwv8_cbo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:iris-scan" {...props}></Icon>
