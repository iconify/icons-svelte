<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tfr-x5gls.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="tfr-x5gls"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:filter-solid" {...props}></Icon>
