<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t0ccmcb0n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="t0ccmcb0n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:more-horizontal-solid" {...props}></Icon>
