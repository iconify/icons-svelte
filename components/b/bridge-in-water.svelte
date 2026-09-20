<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kqumhyl1l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="kqumhyl1l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:bridge-in-water" {...props}></Icon>
