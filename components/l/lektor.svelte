<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s0fe3vb2r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="s0fe3vb2r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:lektor" {...props}></Icon>
