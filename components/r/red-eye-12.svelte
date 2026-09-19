<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e-m5krbes.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="e-m5krbes"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:red-eye-12" {...props}></Icon>
