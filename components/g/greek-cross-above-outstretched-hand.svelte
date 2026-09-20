<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lpful-bqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="lpful-bqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:greek-cross-above-outstretched-hand" {...props}></Icon>
