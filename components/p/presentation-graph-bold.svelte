<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wve9eob_u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wve9eob_u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:presentation-graph-bold" {...props}></Icon>
