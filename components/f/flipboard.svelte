<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qcwdhguoc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="qcwdhguoc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:flipboard" {...props}></Icon>
