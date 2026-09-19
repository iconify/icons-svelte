<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x2u2_tbpp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="x2u2_tbpp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:receipt-forward" {...props}></Icon>
