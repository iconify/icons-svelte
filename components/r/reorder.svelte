<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f5tdmyt-g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f5tdmyt-g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mi:reorder" {...props}></Icon>
