<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qrqw_eyts.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="qrqw_eyts"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:enable-step" {...props}></Icon>
