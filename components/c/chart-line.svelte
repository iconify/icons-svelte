<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xw9u8dbku.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="xw9u8dbku"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:chart-line" {...props}></Icon>
