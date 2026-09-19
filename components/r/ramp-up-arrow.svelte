<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tc3ppnxnh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tc3ppnxnh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:ramp-up-arrow" {...props}></Icon>
