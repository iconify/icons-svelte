<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rd0h3wb9e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rd0h3wb9e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:end-call-rounded-linear" {...props}></Icon>
