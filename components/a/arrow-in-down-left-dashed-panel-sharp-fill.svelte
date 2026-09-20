<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bvd1w9bwf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bvd1w9bwf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:arrow-in-down-left-dashed-panel-sharp-fill" {...props}></Icon>
