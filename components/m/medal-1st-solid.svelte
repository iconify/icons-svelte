<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r-d7wubaf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r-d7wubaf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:medal-1st-solid" {...props}></Icon>
