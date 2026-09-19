<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lsdk4dklm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="lsdk4dklm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:question-bold" {...props}></Icon>
