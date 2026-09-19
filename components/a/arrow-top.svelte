<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kc_a0bb1b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="kc_a0bb1b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bytesize:arrow-top" {...props}></Icon>
