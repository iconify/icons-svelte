<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/ve20-7bvm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ve20-7bvm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:credly" {...props}></Icon>
