<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ac1ym9b_t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<rect transform="rotate(-45 -120466.552 -49977.13)scale(96.7529)" class="ac1ym9b_t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bpmn:gateway" {...props}></Icon>
