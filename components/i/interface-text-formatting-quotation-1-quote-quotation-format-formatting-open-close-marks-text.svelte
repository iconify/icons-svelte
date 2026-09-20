<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wpq5tdlys.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="wpq5tdlys"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-text-formatting-quotation-1-quote-quotation-format-formatting-open-close-marks-text" {...props}></Icon>
