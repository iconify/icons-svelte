<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f-nwl6b2e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f-nwl6b2e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:pencil-x" {...props}></Icon>
