<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/weokkbcgc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="weokkbcgc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:hairdresser-15" {...props}></Icon>
