<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qz94q6zst.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qz94q6zst"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:blur" {...props}></Icon>
