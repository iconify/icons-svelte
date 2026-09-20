<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s_efknval.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="s_efknval"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:overleaf" {...props}></Icon>
