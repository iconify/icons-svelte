<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/giwp7acok.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="giwp7acok"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:drink" {...props}></Icon>
