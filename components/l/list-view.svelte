<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rw4qn3b5a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rw4qn3b5a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:list-view" {...props}></Icon>
