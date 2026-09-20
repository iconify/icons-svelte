<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f1y-tob0w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f1y-tob0w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:bowl-spoon-filled" {...props}></Icon>
