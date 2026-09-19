<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aea1_bb8a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aea1_bb8a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:award" {...props}></Icon>
