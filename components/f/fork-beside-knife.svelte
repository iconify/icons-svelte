<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u_b70x2np.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="u_b70x2np"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:fork-beside-knife" {...props}></Icon>
