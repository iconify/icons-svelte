<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aow45bbhe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aow45bbhe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:hailuo" {...props}></Icon>
