<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x0fbj7bwv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path clip-rule="evenodd" class="x0fbj7bwv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:pilcrow" {...props}></Icon>
