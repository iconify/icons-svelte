<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e8z-_ftin.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e8z-_ftin"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:cherry-heart" {...props}></Icon>
