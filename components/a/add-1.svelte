<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w7ng3y57a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="w7ng3y57a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:add-1" {...props}></Icon>
