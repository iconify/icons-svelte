<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gkdtpob8k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="gkdtpob8k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:chart-area-smooth" {...props}></Icon>
