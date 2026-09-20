<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r43v05j1v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r43v05j1v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:pennant-2-filled" {...props}></Icon>
