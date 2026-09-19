<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rjlu-sn-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="rjlu-sn-b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:face-neutral-filled" {...props}></Icon>
