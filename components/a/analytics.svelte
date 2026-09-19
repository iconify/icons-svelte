<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/us8jlr5kr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="us8jlr5kr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:analytics" {...props}></Icon>
