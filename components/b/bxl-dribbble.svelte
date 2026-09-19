<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aoj_7yb-y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aoj_7yb-y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxl-dribbble" {...props}></Icon>
