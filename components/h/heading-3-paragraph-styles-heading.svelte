<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p13isnbtv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="p13isnbtv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:heading-3-paragraph-styles-heading" {...props}></Icon>
