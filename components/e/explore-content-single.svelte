<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oypkz5_qd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="oypkz5_qd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:explore-content-single" {...props}></Icon>
