<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pf0-nebnj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="pf0-nebnj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:down-small-solid" {...props}></Icon>
