<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lai45lbmt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lai45lbmt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:circle-three-quarter-filled" {...props}></Icon>
