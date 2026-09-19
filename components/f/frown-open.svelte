<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f9xru4bpm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":496,"height":512};
const content = `<path class="f9xru4bpm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-regular:frown-open" {...props}></Icon>
