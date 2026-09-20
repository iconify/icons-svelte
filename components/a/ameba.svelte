<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r8j4ez0ba.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r8j4ez0ba"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:ameba" {...props}></Icon>
