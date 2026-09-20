<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u332-vb3u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u332-vb3u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:plane-tilt-filled" {...props}></Icon>
