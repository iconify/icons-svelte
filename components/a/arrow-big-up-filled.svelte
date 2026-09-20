<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vfk2dz9ub.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vfk2dz9ub"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:arrow-big-up-filled" {...props}></Icon>
