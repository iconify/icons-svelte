<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r07pcme2w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r07pcme2w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:arrow-big-left-short-sharp-fill" {...props}></Icon>
