<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nc96cz0xq.css';
import '../../css/j/jx5abbk2w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="nc96cz0xq"/><path clip-rule="evenodd" class="jx5abbk2w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:mood-surprised-solid" {...props}></Icon>
