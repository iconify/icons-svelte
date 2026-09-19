<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q6ijw0v2b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q6ijw0v2b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:board" {...props}></Icon>
