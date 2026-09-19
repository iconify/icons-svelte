<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/op8whfb1w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="op8whfb1w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:react-logo" {...props}></Icon>
