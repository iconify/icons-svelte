<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fnff0lbjs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fnff0lbjs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:riot-games" {...props}></Icon>
