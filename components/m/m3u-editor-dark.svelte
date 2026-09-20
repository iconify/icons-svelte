<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rl88n_b7j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rl88n_b7j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:m3u-editor-dark" {...props}></Icon>
