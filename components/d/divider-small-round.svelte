<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vwl1g1bld.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vwl1g1bld"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:divider-small-round" {...props}></Icon>
