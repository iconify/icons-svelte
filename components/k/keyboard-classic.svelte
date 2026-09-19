<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rjv6nubai.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="rjv6nubai"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:keyboard-classic" {...props}></Icon>
