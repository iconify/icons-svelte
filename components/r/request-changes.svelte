<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ddiix3uef.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ddiix3uef"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:request-changes" {...props}></Icon>
