<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/da7ij4b_o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":448};
const content = `<path class="da7ij4b_o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:format-color-text" {...props}></Icon>
