<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dbnreyb6m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dbnreyb6m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:filter-2-share" {...props}></Icon>
