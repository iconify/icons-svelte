<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tqa9w_8tr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tqa9w_8tr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:flow-parallel-line" {...props}></Icon>
