<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yyhljoa7g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="yyhljoa7g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:castle-gate-with-battlements" {...props}></Icon>
