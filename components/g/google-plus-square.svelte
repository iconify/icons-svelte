<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v68-995mv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1536};
const content = `<path class="v68-995mv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:google-plus-square" {...props}></Icon>
