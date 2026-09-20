<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s8r_rvb4g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="s8r_rvb4g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:necklace-remix" {...props}></Icon>
