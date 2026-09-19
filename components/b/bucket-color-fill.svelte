<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qd0mnx8hv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="qd0mnx8hv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:bucket-color-fill" {...props}></Icon>
