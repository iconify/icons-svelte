<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dsrnh97vr.css';
import '../../css/k/ksctdbbku.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="dsrnh97vr"/><path class="ksctdbbku"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:bring-forward" {...props}></Icon>
