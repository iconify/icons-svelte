<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b6iuz7bck.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b6iuz7bck"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:lift-1-bold" {...props}></Icon>
