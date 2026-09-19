<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qzgu9ubkz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qzgu9ubkz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:earth" {...props}></Icon>
