<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dffe5p_ib.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="dffe5p_ib"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:fountain-from-ground" {...props}></Icon>
