<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vlubeppvt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":42,"height":32};
const content = `<path class="vlubeppvt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="et:focus" {...props}></Icon>
