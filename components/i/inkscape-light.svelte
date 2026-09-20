<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e2c8clb_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e2c8clb_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:inkscape-light" {...props}></Icon>
