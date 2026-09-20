<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rhsx09bai.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rhsx09bai"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:namur-check-function" {...props}></Icon>
