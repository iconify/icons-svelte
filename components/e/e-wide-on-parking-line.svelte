<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jyse3869w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="jyse3869w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:e-wide-on-parking-line" {...props}></Icon>
