<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ri2-alb5d.css';
import '../../css/c/cdcuj1bfy.css';
import '../../css/y/yeqb12bcq.css';
import '../../css/m/mi4ifbrrd.css';
import '../../css/m/m2o3sh-9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-solid clr-i-solid-path-1 ri2-alb5d"/><path class="cdcuj1bfy clr-i-solid clr-i-solid-path-2"/><path class="clr-i-solid clr-i-solid-path-3 yeqb12bcq"/><path class="clr-i-solid clr-i-solid-path-4 mi4ifbrrd"/><path class="m2o3sh-9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:archive-solid" {...props}></Icon>
