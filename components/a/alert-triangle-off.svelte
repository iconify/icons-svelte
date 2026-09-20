<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/resnd-7qf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="resnd-7qf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:alert-triangle-off" {...props}></Icon>
