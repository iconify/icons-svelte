<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o39udobwc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="o39udobwc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:floating-ip" {...props}></Icon>
