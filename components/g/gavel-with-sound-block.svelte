<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k68etbpof.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="k68etbpof"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:gavel-with-sound-block" {...props}></Icon>
