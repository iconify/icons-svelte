<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sjswz-jcr.css';
import '../../css/j/j_z2tacpf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sjswz-jcr"/><path clip-rule="evenodd" class="j_z2tacpf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:battery-low" {...props}></Icon>
