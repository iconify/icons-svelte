<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/riax18lqr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="riax18lqr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:island-filled" {...props}></Icon>
