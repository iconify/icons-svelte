<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iw3gm_bov.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="iw3gm_bov"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:officer" {...props}></Icon>
