<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b2e31-bzn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b2e31-bzn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:archive-03" {...props}></Icon>
