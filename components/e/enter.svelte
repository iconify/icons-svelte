<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d4hpb_b8f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="d4hpb_b8f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:enter" {...props}></Icon>
