<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kiv2u-b4i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="kiv2u-b4i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:500px-5" {...props}></Icon>
