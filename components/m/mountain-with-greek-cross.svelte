<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qs02qrb6l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="qs02qrb6l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:mountain-with-greek-cross" {...props}></Icon>
