<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rh5ca-63n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rh5ca-63n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-big-up-line-filled" {...props}></Icon>
