<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rew5p0fgf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rew5p0fgf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:gitbook" {...props}></Icon>
