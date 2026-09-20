<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qip7rlb8a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="qip7rlb8a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:face-with-tongue-out-in-circle-outline" {...props}></Icon>
